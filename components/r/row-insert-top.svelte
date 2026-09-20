<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm8y8pmpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm8y8pmpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:row-insert-top" {...props}></Icon>
