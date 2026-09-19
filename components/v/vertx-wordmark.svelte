<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6j0uvbgv.css';
import '../../css/y/y7cjcccww.css';
import '../../css/u/u-6-7yubm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u6j0uvbgv"/><path class="y7cjcccww"/><path class="u-6-7yubm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vertx-wordmark" {...props}></Icon>
