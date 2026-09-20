<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpcok2zar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qpcok2zar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-join" {...props}></Icon>
