<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfq8lxbqj.css';
import '../../css/k/k24wn5bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hfq8lxbqj"/><path clip-rule="evenodd" class="k24wn5bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:spreadsheet-solid" {...props}></Icon>
