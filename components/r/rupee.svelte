<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb1rmu98c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb1rmu98c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:rupee" {...props}></Icon>
