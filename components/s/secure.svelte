<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh611i-hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh611i-hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:secure" {...props}></Icon>
