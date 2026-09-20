<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huizw5bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="huizw5bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status" {...props}></Icon>
