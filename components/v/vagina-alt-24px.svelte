<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwysk2tql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uwysk2tql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:vagina-alt-24px" {...props}></Icon>
