<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-gl1e30s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":1024};
const content = `<path class="k-gl1e30s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:yiiframework" {...props}></Icon>
