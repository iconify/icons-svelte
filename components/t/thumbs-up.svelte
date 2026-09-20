<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfoc4ibca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="sfoc4ibca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:thumbs-up" {...props}></Icon>
