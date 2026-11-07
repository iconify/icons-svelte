<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udz5nqb7v.css';
import '../../css/n/nf63yr-ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udz5nqb7v"/><path clip-rule="evenodd" class="nf63yr-ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:to-pip-bold" {...props}></Icon>
