<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaz4rm-bq.css';
import '../../css/k/kpyqg9v7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uaz4rm-bq"/><path class="kpyqg9v7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-x-20" {...props}></Icon>
