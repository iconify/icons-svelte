<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oob8d17yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oob8d17yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:salt-project" {...props}></Icon>
