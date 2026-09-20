<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf0wplfja.css';
import '../../css/o/o9m46ebzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gf0wplfja"/><path clip-rule="evenodd" class="o9m46ebzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:screenshot-16" {...props}></Icon>
