<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0nhpsynn.css';
import '../../css/b/bxpukbbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="f0nhpsynn"/><path class="bxpukbbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-bold-duotone" {...props}></Icon>
