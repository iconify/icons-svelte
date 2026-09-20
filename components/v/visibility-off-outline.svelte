<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae80w05fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae80w05fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:visibility-off-outline" {...props}></Icon>
