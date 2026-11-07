<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b--gob6xd.css';
import '../../css/s/siuvu-jzd.css';
import '../../css/r/r377frbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b--gob6xd"/><path clip-rule="evenodd" class="siuvu-jzd"/><path class="r377frbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-money-bold" {...props}></Icon>
