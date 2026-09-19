<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvq6_6b7x.css';
import '../../css/q/qxsh5ebmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer dvq6_6b7x"/><path class="duoicon-secondary-layer qxsh5ebmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:smartwatch" {...props}></Icon>
