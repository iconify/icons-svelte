<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/botwy-b2l.css';
import '../../css/i/icimvxwqo.css';
import '../../css/j/j9bcembrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="botwy-b2l"/><path class="icimvxwqo"/><path class="j9bcembrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unimus-dark" {...props}></Icon>
