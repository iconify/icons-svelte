<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kic47lbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kic47lbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stylelint" {...props}></Icon>
