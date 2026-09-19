<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azvt5ojhn.css';
import '../../css/s/s69j4pb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azvt5ojhn"/><path class="s69j4pb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:stateful-set-outlined" {...props}></Icon>
