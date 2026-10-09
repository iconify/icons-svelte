<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq5-hnk5f.css';
import '../../css/r/r4lbnxbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eq5-hnk5f"/><path class="r4lbnxbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:table-tennis-20-bold" {...props}></Icon>
