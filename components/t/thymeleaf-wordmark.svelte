<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk-zpbcpt.css';
import '../../css/v/v1-2libes.css';
import '../../css/g/g3rbux_4u.css';
import '../../css/a/arjsqib7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wk-zpbcpt"/><path class="v1-2libes"/><path class="g3rbux_4u"/><path class="arjsqib7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:thymeleaf-wordmark" {...props}></Icon>
