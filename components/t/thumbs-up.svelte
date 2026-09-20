<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol_ue80zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol_ue80zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:thumbs-up" {...props}></Icon>
