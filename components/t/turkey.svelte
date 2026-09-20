<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/relf4wlgz.css';
import '../../css/v/vlm33lmng.css';
import '../../css/s/snp287xku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="relf4wlgz"/><path class="vlm33lmng"/><path class="snp287xku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:turkey" {...props}></Icon>
