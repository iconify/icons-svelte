<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il_o2nbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il_o2nbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tennis-filled" {...props}></Icon>
