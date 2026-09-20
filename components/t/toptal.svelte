<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi_f7v6xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi_f7v6xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:toptal" {...props}></Icon>
