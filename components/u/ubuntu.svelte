<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4ih49jxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4ih49jxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:ubuntu" {...props}></Icon>
