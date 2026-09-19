<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txbq1dqrx.css';
import '../../css/s/ss55p0bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txbq1dqrx"/><path clip-rule="evenodd" class="ss55p0bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:sample-container-outline" {...props}></Icon>
