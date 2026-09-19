<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uijf33kfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uijf33kfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:tree-option" {...props}></Icon>
