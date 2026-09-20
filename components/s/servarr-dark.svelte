<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eslh_yutq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eslh_yutq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:servarr-dark" {...props}></Icon>
