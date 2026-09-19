<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uul-ip37v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uul-ip37v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-division-slash" {...props}></Icon>
