<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eecf0ebiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eecf0ebiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:slack" {...props}></Icon>
