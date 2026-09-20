<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtgmpjkvu.css';
import '../../css/k/kzggjzb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":800,"top":-38};
const content = `<path class="wtgmpjkvu"/><path class="kzggjzb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unikoo" {...props}></Icon>
