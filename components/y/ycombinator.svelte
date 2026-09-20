<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkwx14bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkwx14bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ycombinator" {...props}></Icon>
