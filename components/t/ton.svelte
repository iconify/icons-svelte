<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy13uwzff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy13uwzff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ton" {...props}></Icon>
