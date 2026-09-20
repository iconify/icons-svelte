<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8wq1obhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o8wq1obhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:thumbs-up" {...props}></Icon>
