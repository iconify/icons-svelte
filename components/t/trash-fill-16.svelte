<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvpwvr8sq.css';
import '../../css/t/tgfroo5dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qvpwvr8sq"/><path class="tgfroo5dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:trash-fill-16" {...props}></Icon>
