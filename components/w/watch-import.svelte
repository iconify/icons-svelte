<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3lcb5b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3lcb5b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watch-import" {...props}></Icon>
