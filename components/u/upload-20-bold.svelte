<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krxvcobsl.css';
import '../../css/c/c6dnn6b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="krxvcobsl"/><path class="c6dnn6b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:upload-20-bold" {...props}></Icon>
