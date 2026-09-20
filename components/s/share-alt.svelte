<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqkvuac7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="rqkvuac7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:share-alt" {...props}></Icon>
