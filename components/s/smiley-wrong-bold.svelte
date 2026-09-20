<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj8_yubde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj8_yubde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smiley-wrong-bold" {...props}></Icon>
