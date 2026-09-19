<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxrr9-byy.css';
import '../../css/r/rtw15hrhy.css';
import '../../css/f/fhjblj9sh.css';
import '../../css/q/q6cfgtwrt.css';
import '../../css/p/p6qbovb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jxrr9-byy"/><path class="rtw15hrhy"/><path class="fhjblj9sh"/><path clip-rule="evenodd" class="q6cfgtwrt"/><path class="p6qbovb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:turbo-wordmark" {...props}></Icon>
