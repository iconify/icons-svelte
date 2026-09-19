<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm8jlwbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm8jlwbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-distribute-center-filled" {...props}></Icon>
