<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyp91c7tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyp91c7tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:silver-airways" {...props}></Icon>
