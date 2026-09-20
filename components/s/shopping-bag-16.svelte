<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhg79_kue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uhg79_kue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:shopping-bag-16" {...props}></Icon>
