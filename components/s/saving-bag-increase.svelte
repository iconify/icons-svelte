<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2lchr8db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2lchr8db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:saving-bag-increase" {...props}></Icon>
