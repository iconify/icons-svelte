<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v34p59b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v34p59b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:schema-off" {...props}></Icon>
