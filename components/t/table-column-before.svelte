<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdq6b-e_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="mdq6b-e_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:table-column-before" {...props}></Icon>
