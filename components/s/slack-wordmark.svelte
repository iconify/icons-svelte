<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptp-sctlm.css';
import '../../css/v/vx-b6wt5v.css';
import '../../css/f/fa8k6ybxx.css';
import '../../css/q/qacc537nh.css';
import '../../css/p/pwddzki1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ptp-sctlm"/><path class="vx-b6wt5v"/><path class="fa8k6ybxx"/><path class="qacc537nh"/><path class="pwddzki1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:slack-wordmark" {...props}></Icon>
