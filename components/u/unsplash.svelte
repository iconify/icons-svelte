<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a670m2dwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a670m2dwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:unsplash" {...props}></Icon>
