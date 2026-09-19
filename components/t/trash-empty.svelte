<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eavwb2bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eavwb2bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:trash-empty" {...props}></Icon>
