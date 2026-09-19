<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wba5tcc0y.css';
import '../../css/n/nm-b5odlu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wba5tcc0y"/><path class="nm-b5odlu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:shuffle-fill" {...props}></Icon>
