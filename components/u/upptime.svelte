<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nde_ibbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nde_ibbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:upptime" {...props}></Icon>
