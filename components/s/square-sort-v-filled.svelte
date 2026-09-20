<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1tasccxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1tasccxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-sort-v-filled" {...props}></Icon>
