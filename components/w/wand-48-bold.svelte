<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfqb5ccjd.css';
import '../../css/x/xh7-42bhx.css';
import '../../css/t/tk2wtebhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sfqb5ccjd"/><path class="xh7-42bhx"/><path class="tk2wtebhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wand-48-bold" {...props}></Icon>
