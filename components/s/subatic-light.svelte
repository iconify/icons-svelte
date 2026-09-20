<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-ou2rbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-ou2rbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:subatic-light" {...props}></Icon>
