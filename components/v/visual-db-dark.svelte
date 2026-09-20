<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbhx6rimm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbhx6rimm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visual-db-dark" {...props}></Icon>
