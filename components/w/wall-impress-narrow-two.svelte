<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h30dj2brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h30dj2brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wall-impress-narrow-two" {...props}></Icon>
