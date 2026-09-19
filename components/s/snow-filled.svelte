<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqqo3spql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqqo3spql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:snow-filled" {...props}></Icon>
