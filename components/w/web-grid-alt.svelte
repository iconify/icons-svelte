<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5kja2bmt.css';
import '../../css/q/qv0ny4dca.css';
import '../../css/d/dboargo5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5kja2bmt"/><path class="qv0ny4dca"/><path class="dboargo5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:web-grid-alt" {...props}></Icon>
