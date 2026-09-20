<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn2h7mb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn2h7mb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rstudioide" {...props}></Icon>
