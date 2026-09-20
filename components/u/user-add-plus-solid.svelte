<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seq_kbcsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="seq_kbcsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-add-plus-solid" {...props}></Icon>
