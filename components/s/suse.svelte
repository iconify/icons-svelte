<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl72_acfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl72_acfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:suse" {...props}></Icon>
