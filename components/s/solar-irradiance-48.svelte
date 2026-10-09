<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyp8s5b_x.css';
import '../../css/i/im7csbc2a.css';
import '../../css/z/zqzklisui.css';
import '../../css/p/pkj7clbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vyp8s5b_x"/><path class="im7csbc2a"/><path class="zqzklisui"/><path class="pkj7clbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-irradiance-48" {...props}></Icon>
