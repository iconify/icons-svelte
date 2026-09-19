<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izz_7wynk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izz_7wynk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:svetle" {...props}></Icon>
