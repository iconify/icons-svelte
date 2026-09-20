<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9ev1ybyr.css';
import '../../css/q/qwm5tjbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ev1ybyr"/><path class="qwm5tjbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:upp" {...props}></Icon>
