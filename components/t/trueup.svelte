<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiywul6jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiywul6jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:trueup" {...props}></Icon>
