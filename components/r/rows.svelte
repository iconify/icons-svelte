<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq2_-jbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yq2_-jbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:rows" {...props}></Icon>
