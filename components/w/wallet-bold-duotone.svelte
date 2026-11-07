<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzylw2bqw.css';
import '../../css/k/kxpdd-d5x.css';
import '../../css/t/tcxp3ubtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hzylw2bqw"/><path class="kxpdd-d5x"/><path class="tcxp3ubtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-bold-duotone" {...props}></Icon>
