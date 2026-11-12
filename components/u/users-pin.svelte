<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3m1z9bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3m1z9bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-pin" {...props}></Icon>
