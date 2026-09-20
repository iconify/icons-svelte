<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5wero0ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5wero0ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-check" {...props}></Icon>
