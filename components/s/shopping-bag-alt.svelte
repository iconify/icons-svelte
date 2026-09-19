<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev7a6mbod.css';
import '../../css/h/hvelf-bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev7a6mbod"/><path class="hvelf-bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shopping-bag-alt" {...props}></Icon>
