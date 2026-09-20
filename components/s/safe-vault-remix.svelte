<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts_wbobix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ts_wbobix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:safe-vault-remix" {...props}></Icon>
