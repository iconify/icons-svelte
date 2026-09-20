<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twacq_bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twacq_bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zabka" {...props}></Icon>
