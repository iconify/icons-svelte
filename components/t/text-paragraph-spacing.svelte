<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abn6swnum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abn6swnum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-paragraph-spacing" {...props}></Icon>
