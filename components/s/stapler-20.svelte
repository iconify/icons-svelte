<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9if2ebze.css';
import '../../css/e/eog-i8bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h9if2ebze"/><path class="eog-i8bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stapler-20" {...props}></Icon>
