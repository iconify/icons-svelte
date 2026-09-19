<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n48w2aczu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n48w2aczu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:trash-full" {...props}></Icon>
