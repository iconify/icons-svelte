<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyf4oybuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyf4oybuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:triangle-plus-2" {...props}></Icon>
