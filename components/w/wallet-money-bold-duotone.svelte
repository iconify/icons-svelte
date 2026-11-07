<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jol1kjm1u.css';
import '../../css/f/fxwq1cqvv.css';
import '../../css/t/tcadmdbou.css';
import '../../css/t/ts72lmbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jol1kjm1u"/><path class="fxwq1cqvv"/><path class="tcadmdbou"/><path class="ts72lmbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-money-bold-duotone" {...props}></Icon>
