<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq_mvabyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq_mvabyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:store-lock" {...props}></Icon>
