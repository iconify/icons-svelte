<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apfcrhlku.css';
import '../../css/g/g-6i4by5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apfcrhlku"/><rect class="g-6i4by5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shapes-alt-filled" {...props}></Icon>
