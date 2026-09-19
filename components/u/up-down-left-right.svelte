<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac0dbpb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ac0dbpb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:up-down-left-right" {...props}></Icon>
