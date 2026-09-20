<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feabg3bhd.css';
import '../../css/x/x4gpywx5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feabg3bhd"/><path class="x4gpywx5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:trash-square-fill" {...props}></Icon>
