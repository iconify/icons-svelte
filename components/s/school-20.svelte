<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3h-3_brx.css';
import '../../css/m/m4dy9ybsj.css';
import '../../css/h/hcrkhjb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c3h-3_brx"/><path class="m4dy9ybsj"/><path class="hcrkhjb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:school-20" {...props}></Icon>
