<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iee2udl7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="iee2udl7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:screen" {...props}></Icon>
