<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bva6ccbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bva6ccbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:step-out" {...props}></Icon>
