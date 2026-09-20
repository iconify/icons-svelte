<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyq-scbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kyq-scbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:separate-vertical-16" {...props}></Icon>
