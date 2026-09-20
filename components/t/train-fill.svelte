<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5zb0lb0o.css';
import '../../css/n/nlgid0bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5zb0lb0o"/><path clip-rule="evenodd" class="nlgid0bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:train-fill" {...props}></Icon>
