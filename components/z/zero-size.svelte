<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul95bdbte.css';
import '../../css/t/thyn37bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ul95bdbte"/><path class="thyn37bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:zero-size" {...props}></Icon>
