<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s01zth5am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1632,"height":1760};
const content = `<path class="s01zth5am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:wheelchair" {...props}></Icon>
