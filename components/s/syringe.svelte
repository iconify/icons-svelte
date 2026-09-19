<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q__q39r5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q__q39r5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:syringe" {...props}></Icon>
