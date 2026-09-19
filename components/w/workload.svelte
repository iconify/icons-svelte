<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5_ojsbrt.css';
import '../../css/q/qesa7pb9s.css';
import '../../css/b/biog0ibqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5_ojsbrt"/><path class="qesa7pb9s"/><path class="biog0ibqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:workload" {...props}></Icon>
