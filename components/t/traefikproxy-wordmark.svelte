<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj588pbsy.css';
import '../../css/l/l10hz5bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mj588pbsy"/><path class="l10hz5bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:traefikproxy-wordmark" {...props}></Icon>
