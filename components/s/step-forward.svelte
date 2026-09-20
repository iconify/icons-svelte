<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u329ly_kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u329ly_kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:step-forward" {...props}></Icon>
