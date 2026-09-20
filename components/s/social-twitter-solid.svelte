<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc-f_171e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc-f_171e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:social-twitter-solid" {...props}></Icon>
