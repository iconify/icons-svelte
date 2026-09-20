<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au31uekiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au31uekiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:triangle-danger" {...props}></Icon>
