<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fff9xgdso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fff9xgdso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:runkit" {...props}></Icon>
