<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-p5fqb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-p5fqb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tornado-solid" {...props}></Icon>
