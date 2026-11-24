<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iigzx5b6a.css';
import '../../css/o/ou4giibdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iigzx5b6a"/><path class="ou4giibdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:volume-2-filled" {...props}></Icon>
