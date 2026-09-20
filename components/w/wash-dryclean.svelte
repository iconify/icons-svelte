<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh_9q-5fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh_9q-5fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:wash-dryclean" {...props}></Icon>
