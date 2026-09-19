<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-oj-cj7f.css';
import '../../css/b/bwibdw4bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-oj-cj7f"/><path class="bwibdw4bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skip-previous-circle" {...props}></Icon>
