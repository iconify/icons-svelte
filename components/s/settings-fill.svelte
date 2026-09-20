<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgo-isbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgo-isbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:settings-fill" {...props}></Icon>
