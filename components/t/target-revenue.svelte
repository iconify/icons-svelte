<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljsebdbqo.css';
import '../../css/k/kb7eai5rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ljsebdbqo"/><path class="kb7eai5rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:target-revenue" {...props}></Icon>
