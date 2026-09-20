<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js50flb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js50flb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:sleep-zzz" {...props}></Icon>
