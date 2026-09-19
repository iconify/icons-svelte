<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj8esq-gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qj8esq-gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:toggle-off" {...props}></Icon>
