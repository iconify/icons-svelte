<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_2eidcoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_2eidcoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:syringe-outline" {...props}></Icon>
