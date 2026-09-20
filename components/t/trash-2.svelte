<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eejy3jbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eejy3jbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:trash-2" {...props}></Icon>
