<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocbpcqota.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocbpcqota"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ticket-gloss" {...props}></Icon>
