<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7-lrabcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7-lrabcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-bag" {...props}></Icon>
